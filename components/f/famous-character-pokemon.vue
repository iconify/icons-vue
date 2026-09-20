<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/d5nequhdi.css';
import '../../css/u/ujk-8v4-a.css';
import '../../css/u/u0ivgpm6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="d5nequhdi"/><path class="ujk-8v4-a"/><path class="u0ivgpm6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:famous-character-pokemon" /></template>
