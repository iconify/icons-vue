<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcx2xzbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="mcx2xzbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:chart" /></template>
