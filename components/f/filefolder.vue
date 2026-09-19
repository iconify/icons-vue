<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dop_v-6bo.css';
import '../../css/q/qcna4wjtc.css';
import '../../css/c/ct7l-y_5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dop_v-6bo"/><path class="qcna4wjtc"/><path class="ct7l-y_5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:filefolder" /></template>
