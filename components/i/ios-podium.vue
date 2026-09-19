<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlshrtbyk.css';
import '../../css/m/m8-q3inzh.css';
import '../../css/c/c3b89bbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mlshrtbyk"/><path class="m8-q3inzh"/><path class="c3b89bbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-podium" /></template>
