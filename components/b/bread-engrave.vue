<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ey476abcz.css';
import '../../css/h/h91u00i2e.css';
import '../../css/j/j-dbpmb7p.css';
import '../../css/c/clsq4v3-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ey476abcz wm-k"/><path class="h91u00i2e wm-shadow"/><path class="j-dbpmb7p wm-k"/><path class="clsq4v3-l wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bread-engrave" /></template>
