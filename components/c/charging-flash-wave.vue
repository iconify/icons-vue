<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w1iepxd2f.css';
import '../../css/u/ukr3sfz5i.css';
import '../../css/d/df-lbeb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w1iepxd2f"/><path class="ukr3sfz5i"/><path class="df-lbeb8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:charging-flash-wave" /></template>
