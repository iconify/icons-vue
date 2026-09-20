<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl5jfab4x.css';
import '../../css/t/tbnuk2u5e.css';
import '../../css/y/ycv4igjlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dl5jfab4x"/><path class="tbnuk2u5e"/><path class="ycv4igjlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cable-manhole" /></template>
