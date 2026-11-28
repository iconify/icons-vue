<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfvn2gbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfvn2gbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:barcode-x" /></template>
