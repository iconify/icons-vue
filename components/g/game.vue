<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jw4-ouqqm.css';
import '../../css/l/l00-agwii.css';
import '../../css/a/anpxsm6qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jw4-ouqqm"/><circle class="l00-agwii"/><circle class="anpxsm6qd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:game" /></template>
