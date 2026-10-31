<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4l39xbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4l39xbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barcode-fill-round" /></template>
