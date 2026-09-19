<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mii39acua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mii39acua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:heart" /></template>
