<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oezb-5bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":410,"height":82};
const content = `<path class="oezb-5bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amazon-music" /></template>
