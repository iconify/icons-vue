<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/g1ygkpenk.css';
import '../../css/e/eq4ku8q_n.css';
import '../../css/q/q58jyg4uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1ygkpenk"/><path class="eq4ku8q_n"/><circle class="q58jyg4uk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ball-basket" /></template>
