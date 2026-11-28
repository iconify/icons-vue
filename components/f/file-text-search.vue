<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thkyisbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thkyisbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-search" /></template>
