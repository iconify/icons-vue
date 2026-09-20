<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp0y3rb0u.css';
import '../../css/z/zxw2msv7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jp0y3rb0u"/><path class="zxw2msv7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-bookmark-1" /></template>
