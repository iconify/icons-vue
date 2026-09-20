<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkjsnojvf.css';
import '../../css/h/hrl1fmafq.css';
import '../../css/c/c4s-zobzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zkjsnojvf"/><path class="hrl1fmafq"/><circle class="c4s-zobzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikiquote" /></template>
