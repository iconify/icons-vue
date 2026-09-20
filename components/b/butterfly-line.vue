<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krmec0bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krmec0bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:butterfly-line" /></template>
