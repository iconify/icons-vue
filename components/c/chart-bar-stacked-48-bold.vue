<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihmii9b0s.css';
import '../../css/t/t-vpait8s.css';
import '../../css/b/bbomh7bop.css';
import '../../css/b/bho8l9bjj.css';
import '../../css/w/wpjkcbchw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihmii9b0s"/><path class="t-vpait8s"/><path class="bbomh7bop"/><path class="bho8l9bjj"/><path class="wpjkcbchw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-stacked-48-bold" /></template>
