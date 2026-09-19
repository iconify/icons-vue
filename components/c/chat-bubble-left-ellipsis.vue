<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgrtvpd0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hgrtvpd0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:chat-bubble-left-ellipsis" /></template>
