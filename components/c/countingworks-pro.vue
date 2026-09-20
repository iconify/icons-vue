<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku--r4boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku--r4boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:countingworks-pro" /></template>
