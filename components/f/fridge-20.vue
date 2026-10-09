<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqdl70b_g.css';
import '../../css/s/st9n28bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nqdl70b_g"/><path class="st9n28bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fridge-20" /></template>
