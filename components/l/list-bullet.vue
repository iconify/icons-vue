<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0m365bkk.css';
import '../../css/x/x4edefbgr.css';
import '../../css/k/kkxmdkb-g.css';
import '../../css/y/yd79u1b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="o0m365bkk"/><circle class="x4edefbgr"/><circle class="kkxmdkb-g"/><circle class="yd79u1b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:list-bullet" /></template>
