<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/ecqz2j0dv.css';
import '../../css/a/ag3a--o6g.css';
import '../../css/h/hu6giccde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ecqz2j0dv"/><path class="ag3a--o6g"/><path class="hu6giccde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:inbox-check" /></template>
