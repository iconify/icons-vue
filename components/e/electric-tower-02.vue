<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/objfwp1iv.css';
import '../../css/a/ao1eykxlw.css';
import '../../css/h/hod5p82lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="objfwp1iv"/><path class="ao1eykxlw"/><path class="hod5p82lh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:electric-tower-02" /></template>
