<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srpby-b4v.css';
import '../../css/e/effr8obxp.css';
import '../../css/m/m3ckqtbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="srpby-b4v"/><path class="effr8obxp"/><path class="m3ckqtbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:diffs-rtl" /></template>
