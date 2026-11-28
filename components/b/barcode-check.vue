<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhmb18b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhmb18b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:barcode-check" /></template>
