<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mk35_kbij.css';
import '../../css/o/o_uca4bwo.css';
import '../../css/p/psft0wb0o.css';
import '../../css/z/zwqelfbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mk35_kbij"/><path class="o_uca4bwo"/><path class="psft0wb0o"/><path class="zwqelfbxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:allowances-no-food-sign" /></template>
