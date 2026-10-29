<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j7y3a7bgh.css';
import '../../css/s/sliiisb3g.css';
import '../../css/v/v8clh90yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j7y3a7bgh"/><path class="sliiisb3g wm-shadow"/><path class="v8clh90yn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gift-engrave" /></template>
