<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/h92865b4u.css';
import '../../css/r/ruoobvlrj.css';
import '../../css/p/p552hfbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h92865b4u"/><path class="ruoobvlrj"/><path class="p552hfbgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-edit" /></template>
