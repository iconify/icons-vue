<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jyjex658h.css';
import '../../css/z/z_2gvg9_c.css';
import '../../css/d/dmh96mbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jyjex658h wm-a"/><path class="wm-k z_2gvg9_c"/><path class="dmh96mbbx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-beard-sketch" /></template>
