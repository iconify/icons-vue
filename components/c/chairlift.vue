<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l59rj_b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="l59rj_b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:chairlift" /></template>
