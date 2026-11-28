<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdi_3fcru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdi_3fcru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:film" /></template>
