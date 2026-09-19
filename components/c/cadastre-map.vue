<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st95u1bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="st95u1bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:cadastre-map" /></template>
