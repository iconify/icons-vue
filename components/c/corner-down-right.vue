<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/t/tg5aa1brc.css';
import '../../css/o/oj4whib-z.css';
import '../../css/r/rh9qoibkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="tg5aa1brc wm-k"/><path class="oj4whib-z wm-a"/><path class="rh9qoibkn wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:corner-down-right" /></template>
