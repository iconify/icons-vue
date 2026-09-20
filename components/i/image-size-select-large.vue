<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfb4mjb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfb4mjb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-size-select-large" /></template>
