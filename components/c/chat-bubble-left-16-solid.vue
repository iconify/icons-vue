<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk-tdu_gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zk-tdu_gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-left-16-solid" /></template>
