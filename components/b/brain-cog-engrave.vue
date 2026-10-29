<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sasjgvbej.css';
import '../../css/c/cb8204bna.css';
import '../../css/s/s8f-ewbkh.css';
import '../../css/l/lvwj8zv0y.css';
import '../../css/d/d-c_quigx.css';
import '../../css/e/ekmlpmtjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sasjgvbej wm-k"/><path class="cb8204bna wm-s"/><path class="s8f-ewbkh wm-shadow"/><path class="lvwj8zv0y wm-k"/><path class="d-c_quigx wm-a"/><path class="ekmlpmtjg wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:brain-cog-engrave" /></template>
