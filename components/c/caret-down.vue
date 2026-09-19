<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfbbxhmml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tfbbxhmml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:caret-down" /></template>
