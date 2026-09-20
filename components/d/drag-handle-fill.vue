<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzogmsbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzogmsbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:drag-handle-fill" /></template>
