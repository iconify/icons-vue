<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wijcs633j.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hh22nib_t.css';
import '../../css/z/zw4p_s46b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wijcs633j"/><g class="dt0cm9dhy primary"><path class="hh22nib_t"/><path class="zw4p_s46b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:banana-duo" /></template>
