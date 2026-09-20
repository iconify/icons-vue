<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb0x0e-xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb0x0e-xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:folder-multiple" /></template>
