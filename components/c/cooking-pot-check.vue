<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osd5_vbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osd5_vbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cooking-pot-check" /></template>
