<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uin1j8l2y.css';
import '../../css/l/lgs3ws6-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uin1j8l2y"/><path class="lgs3ws6-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ford" /></template>
