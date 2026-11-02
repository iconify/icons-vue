<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fivs59bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fivs59bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:auto-hold-fill" /></template>
