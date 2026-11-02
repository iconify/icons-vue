<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrrmcjjtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrrmcjjtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:carrot-line" /></template>
