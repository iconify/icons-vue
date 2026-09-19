<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm3ejky-b.css';
import '../../css/p/pe7z2bb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mm3ejky-b"/><path class="pe7z2bb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-transit-gateway" /></template>
