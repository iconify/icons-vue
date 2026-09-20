<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w38rf6wii.css';
import '../../css/i/i9irkobgy.css';
import '../../css/d/dtgkxxb5c.css';
import '../../css/z/zgfhzacin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w38rf6wii"/><path class="i9irkobgy"/><path class="dtgkxxb5c"/><path class="zgfhzacin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:lock-network" /></template>
