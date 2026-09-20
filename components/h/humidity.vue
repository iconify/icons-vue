<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivjvz2eii.css';
import '../../css/d/d516vkb6g.css';
import '../../css/s/s0_05_nra.css';
import '../../css/h/h01tyzbfu.css';
import '../../css/v/vdjag18vm.css';
import '../../css/c/ccd5ask7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGk33K9cMQ" width="18" height="22" x="3" y="1" maskUnits="userSpaceOnUse" class="ivjvz2eii"><path class="d516vkb6g"/><path class="s0_05_nra"/></mask><g class="h01tyzbfu"><path mask="url(#SVGk33K9cMQ)" class="vdjag18vm"/><path class="ccd5ask7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:humidity" /></template>
