<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty76s9bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty76s9bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:circle-pile" /></template>
