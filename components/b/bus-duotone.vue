<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/osormye2v.css';
import '../../css/x/xo23v9bqf.css';
import '../../css/j/j9wettb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="osormye2v"/><path class="xo23v9bqf"/><path class="j9wettb5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bus-duotone" /></template>
