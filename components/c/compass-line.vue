<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1m_6d7ct.css';
import '../../css/u/uo96j3bcz.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 l1m_6d7ct"/><path class="clr-i-outline clr-i-outline-path-2 uo96j3bcz"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:compass-line" /></template>
