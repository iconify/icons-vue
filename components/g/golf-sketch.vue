<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/io-82l7iw.css';
import '../../css/h/hcqrxvbji.css';
import '../../css/z/z0je37bis.css';
import '../../css/d/dj8dvkbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="io-82l7iw"/><path class="hcqrxvbji wm-k"/><path class="wm-k z0je37bis"/><path class="dj8dvkbjq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:golf-sketch" /></template>
