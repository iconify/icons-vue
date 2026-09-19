<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/g96sazbxl.css';
import '../../css/q/qoebb6b-x.css';
import '../../css/f/fxsft62au.css';
import '../../css/m/maw6_-12u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<defs><mask id="SVGIVSQUd5t"><g class="v3_i3wktz"><path class="g96sazbxl"/><path class="qoebb6b-x"/><path class="fxsft62au"/></g></mask></defs><path mask="url(#SVGIVSQUd5t)" class="maw6_-12u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:disk-one" /></template>
