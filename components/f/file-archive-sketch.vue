<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y9bbmubfg.css';
import '../../css/m/mhi-85bhf.css';
import '../../css/r/rvti0ccgj.css';
import '../../css/e/esqay42vk.css';
import '../../css/m/mzxshtq6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y9bbmubfg"/><path class="mhi-85bhf wm-k"/><path class="rvti0ccgj wm-k"/><path class="esqay42vk wm-k"/><path class="mzxshtq6z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-archive-sketch" /></template>
