<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bd77njbqt.css';
import '../../css/y/y__863ctc.css';
import '../../css/c/cv06d6bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bd77njbqt"/><path class="y__863ctc"/><path class="cv06d6bir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:algorithm" /></template>
