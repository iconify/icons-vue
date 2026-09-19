<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmk6nb6wm.css';
import '../../css/k/kh7uvqjfd.css';
import '../../css/u/uqem58bur.css';
import '../../css/s/sx9388beu.css';
import '../../css/e/egbtnbclf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bmk6nb6wm clr-i-outline--alerted clr-i-outline-path-1--alerted"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted kh7uvqjfd"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted uqem58bur"/><path class="clr-i-outline--alerted clr-i-outline-path-4--alerted sx9388beu"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-5--alerted egbtnbclf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:bar-chart-outline-alerted" /></template>
