<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec08kobtf.css';
import '../../css/m/mweb-cbkq.css';
import '../../css/x/xtbukpbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ec08kobtf"/><path class="mweb-cbkq"/><path class="xtbukpbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kpi-20" /></template>
