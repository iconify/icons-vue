<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-qif68-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-qif68-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:laptop-play" /></template>
