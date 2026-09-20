<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf7b16i3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf7b16i3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chalkboard-off" /></template>
