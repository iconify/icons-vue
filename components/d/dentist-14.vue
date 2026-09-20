<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl991t4hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vl991t4hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:dentist-14" /></template>
