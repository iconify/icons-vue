<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vif0d-bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vif0d-bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:catchup" /></template>
