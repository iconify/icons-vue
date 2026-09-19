<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x21ylpbbz.css';
import '../../css/s/sz8gcyb-v.css';
import '../../css/g/gg44cuvkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x21ylpbbz"/><path class="sz8gcyb-v"/><path class="gg44cuvkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ferry-boat" /></template>
