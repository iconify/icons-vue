<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf_iim5zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf_iim5zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:domain-off" /></template>
