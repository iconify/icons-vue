<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3vwt_bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3vwt_bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-jules" /></template>
