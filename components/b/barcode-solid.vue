<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aljrd8b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aljrd8b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:barcode-solid" /></template>
