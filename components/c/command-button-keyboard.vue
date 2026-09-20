<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/l/lef99f3qs.css';
import '../../css/o/ob-mf0bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="lef99f3qs"/><path class="ob-mf0bkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:command-button-keyboard" /></template>
