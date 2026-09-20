<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igq7hkbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="igq7hkbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:denojs" /></template>
