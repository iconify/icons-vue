<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afybf8_hq.css';
import '../../css/n/naopco_rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="afybf8_hq"/><path class="naopco_rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:core-sample-20-bold" /></template>
