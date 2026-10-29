<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/li_e4ibwl.css';
import '../../css/m/moh80718a.css';
import '../../css/a/astts52ej.css';
import '../../css/t/tz8pg4bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="li_e4ibwl wm-k"/><path class="moh80718a wm-a"/><path class="astts52ej wm-k"/><path class="tz8pg4bwr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flag-checkered-sketch" /></template>
