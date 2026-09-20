<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxe3iy_vo.css';
import '../../css/b/bi25cle2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxe3iy_vo"/><path class="bi25cle2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:acquiremock-light" /></template>
