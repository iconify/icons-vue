<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g86werb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g86werb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-3-line" /></template>
