<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gdo6oebis.css';
import '../../css/j/jq6e3qboz.css';
import '../../css/n/nb53bzx-q.css';
import '../../css/e/eik6x_g1r.css';
import '../../css/w/wkplr4b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gdo6oebis"/><path class="jq6e3qboz"/><path class="nb53bzx-q"/><path class="eik6x_g1r"/><path class="wkplr4b6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fingerprint" /></template>
