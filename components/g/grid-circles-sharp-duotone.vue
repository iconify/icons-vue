<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2_13e-3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2_13e-3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-circles-sharp-duotone" /></template>
