<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb1oskbsf.css';
import '../../css/m/mkb2ul-2f.css';
import '../../css/b/bh86-acav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mb1oskbsf"/><path class="mkb2ul-2f"/><path class="bh86-acav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-donut-20" /></template>
