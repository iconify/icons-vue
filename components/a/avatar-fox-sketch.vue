<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/czwvy50an.css';
import '../../css/s/sk0ha5box.css';
import '../../css/k/k4tj83qrr.css';
import '../../css/k/k9ddrkbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="czwvy50an"/><path class="sk0ha5box wm-k"/><path class="k4tj83qrr wm-k"/><path class="k9ddrkbna wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-fox-sketch" /></template>
