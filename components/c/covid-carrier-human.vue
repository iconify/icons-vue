<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/oa952hwxx.css';
import '../../css/e/e3a4n20td.css';
import '../../css/s/s35wv-bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oa952hwxx"/><path class="e3a4n20td"/><path class="s35wv-bzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:covid-carrier-human" /></template>
