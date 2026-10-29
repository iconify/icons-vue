<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kejil4ukc.css';
import '../../css/h/hlp4e0xzf.css';
import '../../css/d/dc1f5zbic.css';
import '../../css/m/m2ebxhp-u.css';
import '../../css/w/w199b4q7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kejil4ukc wm-k"/><path class="hlp4e0xzf wm-s"/><path class="dc1f5zbic wm-shadow"/><path class="m2ebxhp-u wm-k"/><path class="w199b4q7i wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-cog-engrave" /></template>
