<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ilbc9tc8n.css';
import '../../css/u/uusfhccwf.css';
import '../../css/r/r4a85nb6r.css';
import '../../css/h/hfqd4dtjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="ilbc9tc8n"/><rect class="uusfhccwf"/><path class="r4a85nb6r"/><path class="hfqd4dtjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:linux" /></template>
