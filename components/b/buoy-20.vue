<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdl5g5dgd.css';
import '../../css/e/e2ii3_num.css';
import '../../css/h/hq8tc3ygq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vdl5g5dgd"/><path class="e2ii3_num"/><path class="hq8tc3ygq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:buoy-20" /></template>
