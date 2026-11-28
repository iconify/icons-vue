<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_gb8j0mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i_gb8j0mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:ethernet-fill" /></template>
