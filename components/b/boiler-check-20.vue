<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn29nlyjq.css';
import '../../css/u/uktn-1b8e.css';
import '../../css/x/xm5em6khk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tn29nlyjq"/><path class="uktn-1b8e"/><path class="xm5em6khk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:boiler-check-20" /></template>
