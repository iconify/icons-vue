<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj10lbatj.css';
import '../../css/s/sofn_rf5s.css';
import '../../css/e/ejp_40b7j.css';
import '../../css/n/nzkjcabgj.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 hj10lbatj"/><path class="clr-i-solid clr-i-solid-path-2 sofn_rf5s"/><path class="clr-i-solid clr-i-solid-path-3 ejp_40b7j"/><path class="clr-i-solid clr-i-solid-path-4 nzkjcabgj"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:grid-chart-solid" /></template>
