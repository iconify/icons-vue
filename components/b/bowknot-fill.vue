<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u--0c0_ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u--0c0_ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bowknot-fill" /></template>
