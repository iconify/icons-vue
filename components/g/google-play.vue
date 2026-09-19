<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rovv-r93y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="rovv-r93y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:google-play" /></template>
