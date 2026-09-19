<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjtvz0evg.css';
import '../../css/l/lzklgxbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjtvz0evg"/><path class="lzklgxbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:been-here" /></template>
