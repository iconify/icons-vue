<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sisxtt_vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sisxtt_vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-justify-end-sharp" /></template>
