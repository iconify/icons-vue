<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv91rzblu.css';
import '../../css/q/qsg0-jb6l.css';
import '../../css/r/rndt1hbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bv91rzblu"/><path class="qsg0-jb6l"/><path class="rndt1hbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:fingerprint" /></template>
