<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm3tprbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm3tprbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-2-fill" /></template>
