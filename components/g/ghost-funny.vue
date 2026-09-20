<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lqs17vbsb.css';
import '../../css/j/j3f-cqwca.css';
import '../../css/r/rlsuisb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lqs17vbsb"/><path class="j3f-cqwca"/><path class="rlsuisb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ghost-funny" /></template>
