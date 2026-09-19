<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob_nbubvj.css';
import '../../css/e/e39ud6bwf.css';
import '../../css/q/qaq-ndbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="ob_nbubvj"/><circle class="e39ud6bwf"/><path class="qaq-ndbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:kubernetes-ip-address" /></template>
