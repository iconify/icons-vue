<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zt81p22du.css';
import '../../css/i/i2ilhfsgw.css';
import '../../css/i/i09dt9z0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zt81p22du"/><path class="i2ilhfsgw"/><path class="i09dt9z0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cards" /></template>
