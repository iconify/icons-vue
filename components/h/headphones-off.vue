<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f427lpb1w.css';
import '../../css/s/sswn5w2za.css';
import '../../css/x/x0csbt6wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f427lpb1w"/><path class="sswn5w2za"/><path class="x0csbt6wm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:headphones-off" /></template>
