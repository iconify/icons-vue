<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/p_3hnybns.css';
import '../../css/i/ip_dwfb1g.css';
import '../../css/m/mrawmjblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g transform="translate(4)" class="n1lsf0bnc"><ellipse class="p_3hnybns"/><path class="ip_dwfb1g"/><ellipse class="mrawmjblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:louder-2" /></template>
