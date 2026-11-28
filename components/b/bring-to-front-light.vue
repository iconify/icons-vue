<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3pbcab0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v3pbcab0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bring-to-front-light" /></template>
