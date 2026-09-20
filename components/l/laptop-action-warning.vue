<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rnaonbckk.css';
import '../../css/d/db9u3ij6k.css';
import '../../css/f/fa211pb5n.css';
import '../../css/z/zf5aygbbh.css';
import '../../css/q/q-j7pjang.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rnaonbckk"/><path class="db9u3ij6k"/><path class="fa211pb5n"/><path class="zf5aygbbh"/><path class="q-j7pjang"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:laptop-action-warning" /></template>
