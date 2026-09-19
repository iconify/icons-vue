<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gprj5vbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gprj5vbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-polygon" /></template>
