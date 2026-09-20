<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r7eh21bwh.css';
import '../../css/w/wrpl5eb5t.css';
import '../../css/q/qmvky9b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r7eh21bwh"/><path class="wrpl5eb5t"/><path class="qmvky9b5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:crop-image" /></template>
