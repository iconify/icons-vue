<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ep902kdbw.css';
import '../../css/d/ddo7xcccw.css';
import '../../css/q/qjjcpxbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ep902kdbw"/><path class="ddo7xcccw"/><path class="qjjcpxbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hiking-stick-duotone" /></template>
