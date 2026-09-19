<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4xkvhbmt.css';
import '../../css/l/l09236icr.css';
import '../../css/q/qfnn6de1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t4xkvhbmt"/><circle class="l09236icr"/><path class="qfnn6de1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flashlight-outline" /></template>
