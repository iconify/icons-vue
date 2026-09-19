<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvcg5__wh.css';
import '../../css/b/bxmkebcbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvcg5__wh"/><path class="bxmkebcbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-message-minus" /></template>
