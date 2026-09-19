<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1w22p8jq.css';
import '../../css/i/i388mubqy.css';
import '../../css/v/vc01epbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k1w22p8jq"/><path class="i388mubqy"/><circle class="vc01epbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:location-man-alt" /></template>
