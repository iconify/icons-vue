<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scv2f5bpz.css';
import '../../css/x/xk2zqv2dn.css';
import '../../css/g/g33vo8vvy.css';
import '../../css/u/um41547jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="scv2f5bpz"/><path class="xk2zqv2dn"/><path class="g33vo8vvy"/><path class="um41547jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:construction-crane-20-bold" /></template>
