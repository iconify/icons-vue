<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv_l6fzvt.css';
import '../../css/r/rz8l7i1vb.css';
import '../../css/q/qixglcefr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv_l6fzvt"/><path class="rz8l7i1vb"/><path class="qixglcefr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:ip-outlined" /></template>
