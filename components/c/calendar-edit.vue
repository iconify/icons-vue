<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/o79ijpb8u.css';
import '../../css/z/zqnchacxh.css';
import '../../css/a/ajqhpcbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o79ijpb8u"/><path class="zqnchacxh"/><path class="ajqhpcbca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-edit" /></template>
