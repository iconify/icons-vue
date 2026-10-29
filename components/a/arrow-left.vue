<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqnh6ybes.css';
import '../../css/t/th1hqrxri.css';
import '../../css/w/wx0602c_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqnh6ybes wm-shadow"/><path class="th1hqrxri wm-k"/><path class="wm-k wx0602c_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:arrow-left" /></template>
