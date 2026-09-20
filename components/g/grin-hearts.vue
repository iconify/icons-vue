<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqdg-r_-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rqdg-r_-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-hearts" /></template>
