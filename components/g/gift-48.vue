<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhpycbbzt.css';
import '../../css/g/gxdkw6pqr.css';
import '../../css/k/kp3z9vp1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xhpycbbzt"/><path class="gxdkw6pqr"/><path class="kp3z9vp1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gift-48" /></template>
