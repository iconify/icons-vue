<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhkum03mr.css';
import '../../css/k/k_bic86zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hhkum03mr"/><path class="k_bic86zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gloves-20-bold" /></template>
