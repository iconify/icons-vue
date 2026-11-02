<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afiu3nlin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afiu3nlin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barcode-fill" /></template>
