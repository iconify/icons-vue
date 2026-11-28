<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb7_-3bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb7_-3bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:archive" /></template>
