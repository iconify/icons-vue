<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dss77kb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dss77kb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bed" /></template>
