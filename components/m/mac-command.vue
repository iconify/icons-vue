<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snn4eibbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="snn4eibbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mac-command" /></template>
