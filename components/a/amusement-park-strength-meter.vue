<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tte7b4f3i.css';
import '../../css/y/y_eo9acim.css';
import '../../css/o/oc8vs8bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tte7b4f3i"/><path class="y_eo9acim"/><path class="oc8vs8bfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:amusement-park-strength-meter" /></template>
