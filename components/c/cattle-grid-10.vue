<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g30n8ubuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="g30n8ubuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:cattle-grid-10" /></template>
