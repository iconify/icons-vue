<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv-vaobex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv-vaobex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:align-left-justify" /></template>
