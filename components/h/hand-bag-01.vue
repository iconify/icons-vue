<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e0avo1bww.css';
import '../../css/l/lj9o2zbay.css';
import '../../css/h/h2i-zfbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e0avo1bww"/><path class="lj9o2zbay"/><path class="h2i-zfbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-bag-01" /></template>
