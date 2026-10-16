<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opebgib4l.css';
import '../../css/o/o92awt_ps.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="opebgib4l"/><path class="o92awt_ps"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gravity-base-20" /></template>
