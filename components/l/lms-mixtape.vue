<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj9--rywt.css';
import '../../css/r/rr9a01bpl.css';
import '../../css/d/dz4yw6hux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oj9--rywt"/><path class="rr9a01bpl"/><path class="dz4yw6hux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lms-mixtape" /></template>
