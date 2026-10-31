<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/l/l41_pab0n.css';
import '../../css/l/l83m8bbbg.css';
import '../../css/w/wcaq-jbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="l41_pab0n wm-k"/><path class="l83m8bbbg wm-a"/><path class="wcaq-jbkf wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:arrow-up-right" /></template>
