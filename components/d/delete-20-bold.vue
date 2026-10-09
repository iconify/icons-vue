<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-p6gpbin.css';
import '../../css/d/dnun0_bjo.css';
import '../../css/m/mldtn5bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i-p6gpbin"/><path class="dnun0_bjo"/><path class="mldtn5bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:delete-20-bold" /></template>
