<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szae48b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szae48b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-export-outline" /></template>
