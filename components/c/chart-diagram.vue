<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwj65_bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hwj65_bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-diagram" /></template>
