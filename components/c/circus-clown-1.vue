<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qsoymgbwb.css';
import '../../css/y/yc3ce7q3e.css';
import '../../css/p/pl9qoeb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qsoymgbwb"/><path class="yc3ce7q3e"/><path class="pl9qoeb3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:circus-clown-1" /></template>
