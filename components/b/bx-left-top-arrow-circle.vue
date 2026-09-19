<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgh3h12lr.css';
import '../../css/f/fmv_7cgeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgh3h12lr"/><path class="fmv_7cgeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-left-top-arrow-circle" /></template>
