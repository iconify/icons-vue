<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlm-d1pfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="mlm-d1pfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:document-words" /></template>
