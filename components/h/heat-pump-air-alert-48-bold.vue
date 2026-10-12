<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm13-txuu.css';
import '../../css/d/dhdywzrps.css';
import '../../css/l/lo-76q32a.css';
import '../../css/h/hfkbjdban.css';
import '../../css/c/c3xvfibhp.css';
import '../../css/y/ygtv74bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gm13-txuu"/><path class="dhdywzrps"/><path class="lo-76q32a"/><path class="hfkbjdban"/><path class="c3xvfibhp"/><path class="ygtv74bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-air-alert-48-bold" /></template>
