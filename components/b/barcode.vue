<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkd4cdchu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkd4cdchu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:barcode" /></template>
