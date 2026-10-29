<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mykchfbxc.css';
import '../../css/f/foi40nbza.css';
import '../../css/l/luqu_mfyf.css';
import '../../css/s/s4uk5n7uw.css';
import '../../css/h/hnxobrbrn.css';
import '../../css/o/ohlg0wbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mykchfbxc wm-k"/><path class="foi40nbza wm-s"/><path class="luqu_mfyf wm-shadow"/><path class="s4uk5n7uw wm-k"/><path class="hnxobrbrn wm-a"/><path class="ohlg0wbaj wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:champagne-toast-engrave" /></template>
