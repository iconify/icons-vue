<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2l2_ebga.css';
import '../../css/g/gjxcd2b_y.css';
import '../../css/e/ebxyc5bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i2l2_ebga"/><path class="gjxcd2b_y"/><path class="ebxyc5bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carrot-48" /></template>
