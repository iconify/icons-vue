<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tj134_beb.css';
import '../../css/e/ebt74uolj.css';
import '../../css/g/g6lfx9bco.css';
import '../../css/c/cpu9b4b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tj134_beb"/><path class="ebt74uolj wm-a"/><path class="g6lfx9bco wm-k"/><path class="cpu9b4b-s wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-percent-sketch" /></template>
