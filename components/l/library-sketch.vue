<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gie3geb9a.css';
import '../../css/f/f33oscbyn.css';
import '../../css/o/o_ba6fyis.css';
import '../../css/d/ds28d454v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gie3geb9a"/><path class="f33oscbyn wm-k"/><path class="o_ba6fyis wm-k"/><path class="ds28d454v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:library-sketch" /></template>
