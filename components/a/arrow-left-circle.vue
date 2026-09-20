<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/got39gbyx.css';
import '../../css/b/b6lqqvb2b.css';
import '../../css/n/n5pc76bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="got39gbyx"/><path class="b6lqqvb2b"/><path class="n5pc76bja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-left-circle" /></template>
