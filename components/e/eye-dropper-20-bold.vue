<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1hov4txr.css';
import '../../css/o/o_hufdbvo.css';
import '../../css/u/ujk3pta6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m1hov4txr"/><path class="o_hufdbvo"/><path class="ujk3pta6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-dropper-20-bold" /></template>
