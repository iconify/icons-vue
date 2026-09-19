<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq1_nmbap.css';
import '../../css/v/vd0yurcnj.css';
import '../../css/w/wgnfps2so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uq1_nmbap"/><path class="vd0yurcnj"/><path class="wgnfps2so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:apify" /></template>
