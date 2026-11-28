<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_l4hqb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_l4hqb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:barcode-search" /></template>
