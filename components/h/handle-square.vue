<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/h/hrq90hfel.css';
import '../../css/n/nffv20brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><circle class="hrq90hfel"/><rect class="nffv20brn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:handle-square" /></template>
