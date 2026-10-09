<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsv5h1yxl.css';
import '../../css/r/r67i5vbwt.css';
import '../../css/f/f2v26bkcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gsv5h1yxl"/><path class="r67i5vbwt"/><path class="f2v26bkcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charger-home-48-bold" /></template>
