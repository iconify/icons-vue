<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aza7d0f_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aza7d0f_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bowl-2-line" /></template>
