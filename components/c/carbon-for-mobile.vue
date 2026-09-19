<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7wssw66i.css';
import '../../css/t/ttkwngbky.css';
import '../../css/l/lhg-6wa8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d7wssw66i"/><circle class="ttkwngbky"/><path class="lhg-6wa8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:carbon-for-mobile" /></template>
