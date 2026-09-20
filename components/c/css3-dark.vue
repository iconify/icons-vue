<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kduu9pbdz.css';
import '../../css/x/xpct6_bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kduu9pbdz"/><path class="xpct6_bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:css3-dark" /></template>
