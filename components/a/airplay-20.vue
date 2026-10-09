<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve2d5cbgv.css';
import '../../css/a/ay_ybxb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ve2d5cbgv"/><path class="ay_ybxb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:airplay-20" /></template>
