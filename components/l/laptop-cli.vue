<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gmeuf3gzy.css';
import '../../css/t/tvc4p7bak.css';
import '../../css/u/uzfykfbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="gmeuf3gzy"/><path clip-rule="evenodd" class="tvc4p7bak"/><path class="uzfykfbxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:laptop-cli" /></template>
