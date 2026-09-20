<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dfsvjbgyy.css';
import '../../css/m/mjaimm-ui.css';
import '../../css/x/x2-3lfqme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dfsvjbgyy"/><path class="mjaimm-ui"/><path class="x2-3lfqme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flag-1" /></template>
