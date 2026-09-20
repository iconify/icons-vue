<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw8sdm1be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw8sdm1be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:htc-vive" /></template>
