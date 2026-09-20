<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veuj-zb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="veuj-zb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-laboratory" /></template>
