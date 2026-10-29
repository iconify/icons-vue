<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cuclwhyqo.css';
import '../../css/u/uoaa1gawm.css';
import '../../css/k/kntysj6im.css';
import '../../css/j/jwtq0cbry.css';
import '../../css/x/xuf368byp.css';
import '../../css/n/ndf5tbb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cuclwhyqo wm-k"/><path class="uoaa1gawm wm-k"/><path class="kntysj6im wm-k"/><path class="jwtq0cbry wm-a"/><path class="wm-a xuf368byp"/><path class="ndf5tbb2x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-list-sketch" /></template>
