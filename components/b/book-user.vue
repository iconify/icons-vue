<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/le2xeyb8c.css';
import '../../css/i/is7m5ub9x.css';
import '../../css/c/c-8fi9pzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="le2xeyb8c"/><path class="is7m5ub9x"/><path class="c-8fi9pzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-user" /></template>
