<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx8y2ds-k.css';
import '../../css/i/iktc6lbdf.css';
import '../../css/o/oli4db1ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="iktc6lbdf"/><path class="oli4db1ir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:align-bottom" /></template>
