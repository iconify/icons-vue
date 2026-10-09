<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc7msjb7m.css';
import '../../css/b/bdgh64buo.css';
import '../../css/g/gxsgqfbzc.css';
import '../../css/q/qnfhe3b6k.css';
import '../../css/t/trfzb5bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oc7msjb7m"/><path class="bdgh64buo"/><path class="gxsgqfbzc"/><path class="qnfhe3b6k"/><path class="trfzb5bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:curtailment-20-bold" /></template>
