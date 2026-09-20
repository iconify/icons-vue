<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj1fhobwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj1fhobwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dolby" /></template>
