<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yegc-sbkr.css';
import '../../css/l/l390iecly.css';
import '../../css/o/oxf-v8-ae.css';
import '../../css/d/d1ccs6skz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yegc-sbkr"/><path class="l390iecly"/><path class="oxf-v8-ae"/><path class="d1ccs6skz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kchat" /></template>
