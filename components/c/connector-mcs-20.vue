<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnjq5zbqb.css';
import '../../css/f/f7q3gxb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dnjq5zbqb"/><path class="f7q3gxb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-mcs-20" /></template>
