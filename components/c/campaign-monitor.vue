<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fja-axsxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fja-axsxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:campaign-monitor" /></template>
