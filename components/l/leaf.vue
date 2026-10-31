<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/m/mv2ksxb6o.css';
import '../../css/h/hxmvs7bhc.css';
import '../../css/p/pg6c6hbqu.css';
import '../../css/m/mp77goa1w.css';
import '../../css/f/fuo7qcb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="mv2ksxb6o"/><path class="hxmvs7bhc wm-shine"/><path class="pg6c6hbqu wm-k"/><path class="mp77goa1w wm-a"/><path class="fuo7qcb4u wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:leaf" /></template>
