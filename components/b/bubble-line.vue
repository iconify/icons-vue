<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsun2obik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsun2obik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bubble-line" /></template>
