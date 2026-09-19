<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2pi-7bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g2pi-7bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:app-store-ios" /></template>
