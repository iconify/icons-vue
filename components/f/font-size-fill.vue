<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iccc16bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iccc16bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:font-size-fill" /></template>
