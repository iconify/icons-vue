<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n5-9xvbob.css';
import '../../css/f/fse-o4bbv.css';
import '../../css/a/adnxrhb5g.css';
import '../../css/p/p43mkbb9d.css';
import '../../css/y/y-xkudbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n5-9xvbob"/><path class="fse-o4bbv wm-shadow"/><path class="adnxrhb5g"/><path class="p43mkbb9d"/><path class="y-xkudbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bandage-engrave" /></template>
