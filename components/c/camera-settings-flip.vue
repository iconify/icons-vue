<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/izx1dccqx.css';
import '../../css/e/ebj5f2bdx.css';
import '../../css/u/u-dbt3usg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="izx1dccqx"/><path class="ebj5f2bdx"/><path class="u-dbt3usg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:camera-settings-flip" /></template>
