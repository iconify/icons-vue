<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkk764efu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qkk764efu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hand-point-down" /></template>
