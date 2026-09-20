<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/na411obky.css';
import '../../css/d/dmfni0bso.css';
import '../../css/f/f-srkbcuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="na411obky"/><path class="dmfni0bso"/><path class="f-srkbcuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-in-linear" /></template>
