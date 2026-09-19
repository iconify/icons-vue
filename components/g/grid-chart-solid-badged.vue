<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj10lbatj.css';
import '../../css/e/e9-b7jbhp.css';
import '../../css/e/ejp_40b7j.css';
import '../../css/n/nzkjcabgj.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged hj10lbatj"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged e9-b7jbhp"/><path class="clr-i-solid--badged clr-i-solid-path-3--badged ejp_40b7j"/><path class="clr-i-solid--badged clr-i-solid-path-4--badged nzkjcabgj"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-5--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:grid-chart-solid-badged" /></template>
