<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzttz05cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":417,"height":768};
const content = `<path class="yzttz05cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:iphone" /></template>
