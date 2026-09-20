<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/ximv8ihgl.css';
import '../../css/p/pl259k1fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ximv8ihgl"/><path class="pl259k1fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:danmaku-on-fill" /></template>
