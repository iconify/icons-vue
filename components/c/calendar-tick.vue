<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/ph3kch2zm.css';
import '../../css/x/xu3g27b7k.css';
import '../../css/t/tq0y-p-0s.css';
import '../../css/a/ajqhpcbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ph3kch2zm"/><path class="xu3g27b7k"/><path class="tq0y-p-0s"/><path class="ajqhpcbca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-tick" /></template>
