<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1hdbtm8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1hdbtm8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-5-line" /></template>
