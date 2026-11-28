<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/das1e-7xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="das1e-7xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cake" /></template>
