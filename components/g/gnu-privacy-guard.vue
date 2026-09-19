<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7yodhbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p7yodhbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gnu-privacy-guard" /></template>
