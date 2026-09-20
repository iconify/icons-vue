<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g51az2k9u.css';
import '../../css/y/y5kp75b4f.css';
import '../../css/z/zocdt8btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g51az2k9u"/><path class="y5kp75b4f"/><path class="zocdt8btw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:hierarchy" /></template>
