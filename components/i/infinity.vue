<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz9k_iy5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tz9k_iy5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:infinity" /></template>
