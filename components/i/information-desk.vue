<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wy9y5naby.css';
import '../../css/q/qt392mi1w.css';
import '../../css/k/k4p-mx6zk.css';
import '../../css/d/d9tj3eb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wy9y5naby"/><path class="qt392mi1w"/><path class="k4p-mx6zk"/><path class="d9tj3eb5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:information-desk" /></template>
