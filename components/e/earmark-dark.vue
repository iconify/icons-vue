<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se_9qubxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":180,"height":180};
const content = `<path class="se_9qubxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:earmark-dark" /></template>
