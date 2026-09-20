<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/we9b9_p-a.css';
import '../../css/q/qzzo5nbdd.css';
import '../../css/x/xcrrugbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="we9b9_p-a"/><path class="qzzo5nbdd"/><path class="xcrrugbsn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:focus-camera-auto" /></template>
