<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zga537btf.css';
import '../../css/t/tue7ke1ug.css';
import '../../css/b/b8357wzya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zga537btf"/><path class="tue7ke1ug wm-shadow"/><path class="b8357wzya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:droplet-engrave" /></template>
