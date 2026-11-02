<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsl6db1of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsl6db1of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-fill" /></template>
