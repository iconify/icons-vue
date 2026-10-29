<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j3dcsdbvr.css';
import '../../css/o/okzts2beh.css';
import '../../css/t/tkbhou2iz.css';
import '../../css/d/dn06k0bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j3dcsdbvr wm-k"/><path class="okzts2beh wm-a"/><path class="tkbhou2iz wm-k"/><path class="dn06k0bio wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fingerprint-sketch" /></template>
