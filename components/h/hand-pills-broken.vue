<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l4s1krj7f.css';
import '../../css/o/ob35u0bzq.css';
import '../../css/r/r_s45d2gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l4s1krj7f"/><path class="ob35u0bzq"/><path class="r_s45d2gs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-pills-broken" /></template>
