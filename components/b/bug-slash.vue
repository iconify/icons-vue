<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/o7psohbfh.css';
import '../../css/q/q90fv6qec.css';
import '../../css/a/a2wwsgbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7psohbfh"/><path class="q90fv6qec"/><path class="a2wwsgbar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bug-slash" /></template>
