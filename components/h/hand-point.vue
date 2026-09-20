<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh80sfblh.css';
import '../../css/t/t7bv4xpss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kh80sfblh"/><path class="t7bv4xpss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-point" /></template>
