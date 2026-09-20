<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd_610ovi.css';
import '../../css/r/r0k4s_6cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qd_610ovi"/><path class="r0k4s_6cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hhf-technology" /></template>
