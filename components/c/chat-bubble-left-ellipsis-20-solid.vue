<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u43xfbckx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u43xfbckx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-left-ellipsis-20-solid" /></template>
