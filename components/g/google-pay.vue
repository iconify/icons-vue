<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb8cuq49r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb8cuq49r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-pay" /></template>
