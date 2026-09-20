<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbt6qobfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbt6qobfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:diamond-line" /></template>
