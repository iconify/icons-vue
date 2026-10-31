<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jw_axvbpc.css';
import '../../css/r/r661y34wk.css';
import '../../css/r/replhxbbv.css';
import '../../css/v/vi68j6y1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jw_axvbpc wm-k"/><path class="r661y34wk wm-k"/><path class="replhxbbv wm-k"/><path class="vi68j6y1t wm-shadow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:door-open" /></template>
