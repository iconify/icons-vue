<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d94nysxlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d94nysxlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-pay" /></template>
