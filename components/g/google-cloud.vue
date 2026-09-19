<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p05_7bbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p05_7bbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:google-cloud" /></template>
