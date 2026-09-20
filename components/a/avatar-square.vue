<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebi_z2qhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebi_z2qhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:avatar-square" /></template>
