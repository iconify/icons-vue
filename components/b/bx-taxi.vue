<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx5pt5wxs.css';
import '../../css/d/drdla2-9e.css';
import '../../css/w/wdin9-bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx5pt5wxs"/><circle class="drdla2-9e"/><circle class="wdin9-bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-taxi" /></template>
