<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwtfp-_ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwtfp-_ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:angry-line" /></template>
