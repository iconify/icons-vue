<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uyl-ddcwz.css';
import '../../css/a/a-wvml5ct.css';
import '../../css/e/e4ii85bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uyl-ddcwz"/><path clip-rule="evenodd" class="a-wvml5ct"/><path class="e4ii85bpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:calendar-add-fill" /></template>
