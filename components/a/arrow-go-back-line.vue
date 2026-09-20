<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo86ez2pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo86ez2pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-go-back-line" /></template>
