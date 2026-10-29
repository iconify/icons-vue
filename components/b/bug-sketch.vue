<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v2xcx5bmn.css';
import '../../css/z/z3ea-3bkc.css';
import '../../css/t/t39qexw8w.css';
import '../../css/a/a-_1mcwru.css';
import '../../css/s/ssz_teloc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v2xcx5bmn"/><path class="wm-k z3ea-3bkc"/><path class="t39qexw8w wm-a"/><path class="a-_1mcwru wm-k"/><path class="ssz_teloc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bug-sketch" /></template>
