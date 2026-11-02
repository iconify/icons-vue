<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfk5-2ass.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfk5-2ass"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:danmaku-line" /></template>
