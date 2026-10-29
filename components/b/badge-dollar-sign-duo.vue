<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lfddx0u7v.css';
import '../../css/s/sv9nxnpyo.css';
import '../../css/h/hooc3vbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lfddx0u7v"/><path class="sv9nxnpyo wm-a"/><path class="hooc3vbcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-dollar-sign-duo" /></template>
