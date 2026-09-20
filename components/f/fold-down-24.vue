<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7xt4ebhe.css';
import '../../css/q/q8d80dxoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7xt4ebhe"/><path class="q8d80dxoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fold-down-24" /></template>
