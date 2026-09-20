<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzpaq-eyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzpaq-eyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:coderwall" /></template>
