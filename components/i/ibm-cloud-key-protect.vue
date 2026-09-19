<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mre-spuzg.css';
import '../../css/r/rwhb52b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mre-spuzg"/><path class="rwhb52b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-key-protect" /></template>
