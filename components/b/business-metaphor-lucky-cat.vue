<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gjccdsbql.css';
import '../../css/s/sqzg-pbzs.css';
import '../../css/d/dxs3hib_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gjccdsbql"/><path class="sqzg-pbzs"/><path class="dxs3hib_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:business-metaphor-lucky-cat" /></template>
