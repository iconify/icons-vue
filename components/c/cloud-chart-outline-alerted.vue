<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmk6nb6wm.css';
import '../../css/l/lqtw584oo.css';
import '../../css/z/zfepgc0mr.css';
import '../../css/e/egbtnbclf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bmk6nb6wm clr-i-outline--alerted clr-i-outline-path-1--alerted"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted lqtw584oo"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted zfepgc0mr"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-4--alerted egbtnbclf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:cloud-chart-outline-alerted" /></template>
