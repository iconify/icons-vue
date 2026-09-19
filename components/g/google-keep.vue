<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m22-05bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m22-05bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:google-keep" /></template>
