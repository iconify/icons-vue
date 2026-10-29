<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/msq31bcno.css';
import '../../css/z/zdgcjvxqz.css';
import '../../css/d/dto6yifku.css';
import '../../css/e/ebfe2acus.css';
import '../../css/d/d2ecqac4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="msq31bcno wm-k"/><path class="wm-a zdgcjvxqz"/><path class="dto6yifku wm-shadow"/><path class="ebfe2acus wm-k"/><path class="d2ecqac4y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-engrave" /></template>
