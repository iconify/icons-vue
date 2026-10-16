<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5i0nibgo.css';
import '../../css/h/hmt9evbnn.css';
import '../../css/w/we9u0mx2s.css';
import '../../css/a/atyhtibwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r5i0nibgo"/><path class="hmt9evbnn"/><path class="we9u0mx2s"/><path class="atyhtibwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corn-48" /></template>
