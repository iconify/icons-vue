<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su4ixfbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su4ixfbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-loader-alt" /></template>
