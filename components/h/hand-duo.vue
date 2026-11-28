<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os5-1c1zv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o54a_403x.css';
import '../../css/l/lvufu95qt.css';
import '../../css/t/tgt0jgbav.css';
import '../../css/t/tjft3ex5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os5-1c1zv secondary"/><g class="dt0cm9dhy primary"><path class="o54a_403x"/><path class="lvufu95qt"/><path class="tgt0jgbav"/><path class="tjft3ex5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hand-duo" /></template>
