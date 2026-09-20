<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp_eem7eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp_eem7eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-sharp-fill" /></template>
