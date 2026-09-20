<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0a5y4b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0a5y4b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:barcode-line" /></template>
