<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nni0lirok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nni0lirok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:circle-info-solid" /></template>
