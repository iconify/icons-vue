<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iemmtbc_j.css';
import '../../css/j/jr2o5bbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":346,"height":434};
const content = `<path class="iemmtbc_j"/><path class="cls-1 jr2o5bbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:heimdall" /></template>
