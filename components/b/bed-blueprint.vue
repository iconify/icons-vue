<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/mpgrsdwrf.css';
import '../../css/d/dk4za7bzt.css';
import '../../css/k/knq75eb6v.css';
import '../../css/s/s37zulbpr.css';
import '../../css/p/ph19weu1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="mpgrsdwrf wm-deco"/><path class="dk4za7bzt wm-deco"/><path class="knq75eb6v wm-k"/><path class="s37zulbpr wm-a"/><path class="ph19weu1z wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bed-blueprint" /></template>
