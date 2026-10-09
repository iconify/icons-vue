<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8yec1dno.css';
import '../../css/c/cntw57bva.css';
import '../../css/v/vo5xihh_v.css';
import '../../css/d/dtp5yccxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c8yec1dno"/><path class="cntw57bva"/><path class="vo5xihh_v"/><path class="dtp5yccxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:construction-crane-48-bold" /></template>
