<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/ml9vscc8q.css';
import '../../css/i/iwxpr45qa.css';
import '../../css/k/k2yb2obuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ml9vscc8q"/><path class="iwxpr45qa"/><path class="k2yb2obuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:locker-room-wash-hands" /></template>
