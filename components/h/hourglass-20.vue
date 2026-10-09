<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbcynr_zb.css';
import '../../css/m/mvifll_hv.css';
import '../../css/z/zoq1otb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nbcynr_zb"/><path class="mvifll_hv"/><path class="zoq1otb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hourglass-20" /></template>
