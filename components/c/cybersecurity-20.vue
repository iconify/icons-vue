<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc9itcbez.css';
import '../../css/d/d_av7khvm.css';
import '../../css/y/ymo2yhixw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sc9itcbez"/><path class="d_av7khvm"/><path class="ymo2yhixw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cybersecurity-20" /></template>
