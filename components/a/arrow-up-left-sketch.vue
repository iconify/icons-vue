<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hh72aib6v.css';
import '../../css/h/hkqdwxbdb.css';
import '../../css/o/oshi5ze9z.css';
import '../../css/o/ozywhg4qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hh72aib6v wm-k"/><path class="hkqdwxbdb wm-a"/><path class="oshi5ze9z wm-k"/><path class="ozywhg4qo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-left-sketch" /></template>
