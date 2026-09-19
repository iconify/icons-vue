<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5w0p9byi.css';
import '../../css/s/sm_16-bij.css';
import '../../css/r/rpjwekbqt.css';
import '../../css/e/e6ec1d1ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="x5w0p9byi"/><circle class="sm_16-bij"/><path class="rpjwekbqt"/><path class="e6ec1d1ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cart-outline" /></template>
