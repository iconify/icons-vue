<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hkp7a4bwa.css';
import '../../css/r/rd7d6grar.css';
import '../../css/f/f1x8zjlhe.css';
import '../../css/a/aamnfraot.css';
import '../../css/r/rkv9j1-pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hkp7a4bwa wm-deco"/><path class="rd7d6grar wm-k"/><path class="f1x8zjlhe wm-k"/><path class="aamnfraot wm-k"/><path class="rkv9j1-pe wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:arrow-down-left" /></template>
