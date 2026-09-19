<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj10lbatj.css';
import '../../css/n/nwa3eqi_r.css';
import '../../css/e/ejp_40b7j.css';
import '../../css/n/nzkjcabgj.css';
import '../../css/e/egbtnbclf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted hj10lbatj"/><path class="clr-i-solid--alerted clr-i-solid-path-2--alerted nwa3eqi_r"/><path class="clr-i-solid--alerted clr-i-solid-path-3--alerted ejp_40b7j"/><path class="clr-i-solid--alerted clr-i-solid-path-4--alerted nzkjcabgj"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-5--alerted egbtnbclf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:grid-chart-solid-alerted" /></template>
