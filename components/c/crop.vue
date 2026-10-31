<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/e3zc47bax.css';
import '../../css/o/o727glb2e.css';
import '../../css/h/hnchhcx2q.css';
import '../../css/y/y55iiobqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="e3zc47bax wm-shadow"/><path class="o727glb2e wm-shadow"/><path class="hnchhcx2q"/><path class="y55iiobqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:crop" /></template>
