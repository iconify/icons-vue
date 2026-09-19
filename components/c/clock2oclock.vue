<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt893gged.css';
import '../../css/e/eg39dacou.css';
import '../../css/k/k-dv7v_af.css';
import '../../css/r/rzeq_svbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gt893gged"/><path class="eg39dacou"/><path class="k-dv7v_af"/><path class="rzeq_svbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:clock2oclock" /></template>
