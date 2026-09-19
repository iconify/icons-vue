<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy2zf99lb.css';
import '../../css/t/tf5xj-bsz.css';
import '../../css/k/koofvxt_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fy2zf99lb"/><circle class="tf5xj-bsz"/><circle class="koofvxt_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:car-outline" /></template>
