<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qere4db2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qere4db2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:barcode-check" /></template>
