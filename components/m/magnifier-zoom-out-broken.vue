<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kjxg36b_m.css';
import '../../css/c/cq5xp9n1p.css';
import '../../css/x/x09loybdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kjxg36b_m"/><path class="cq5xp9n1p"/><path class="x09loybdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-zoom-out-broken" /></template>
