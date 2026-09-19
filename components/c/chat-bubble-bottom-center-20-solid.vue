<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylwh1bc5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ylwh1bc5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-bottom-center-20-solid" /></template>
