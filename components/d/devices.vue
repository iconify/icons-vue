<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b69dij5rx.css';
import '../../css/m/muxrmeneg.css';
import '../../css/o/oqmofb2lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b69dij5rx"/><path class="muxrmeneg"/><path class="oqmofb2lj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:devices" /></template>
