<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e127p9cjs.css';
import '../../css/i/izvj3goyw.css';
import '../../css/l/louq1sjgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="e127p9cjs"/><path class="izvj3goyw wm-a"/><path class="louq1sjgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bug-duo" /></template>
