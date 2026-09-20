<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tbl4j-bom.css';
import '../../css/g/gnrb8ib6h.css';
import '../../css/m/mvx2c_b9q.css';
import '../../css/k/ko6o-6b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tbl4j-bom"/><path class="gnrb8ib6h"/><path class="mvx2c_b9q"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:confounded-circle-broken" /></template>
