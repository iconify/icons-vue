<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm77mwb7x.css';
import '../../css/r/rjes9k1zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="qm77mwb7x"/><path class="rjes9k1zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:cube-3d" /></template>
