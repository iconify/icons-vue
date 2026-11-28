<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej3j5_fhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej3j5_fhc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-off-page-duotone" /></template>
