<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/ybfqy0wjb.css';
import '../../css/m/mhdr543mh.css';
import '../../css/b/bkja6hbdm.css';
import '../../css/a/abddbewdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco ybfqy0wjb"/><path class="mhdr543mh wm-deco"/><path class="bkja6hbdm"/><path class="abddbewdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-center-blueprint" /></template>
