<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/puw9pfmix.css';
import '../../css/r/rxtl2ibrn.css';
import '../../css/a/ao_0jqt1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="puw9pfmix"/><path class="rxtl2ibrn"/><path class="ao_0jqt1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:equalizer-phone-application-2" /></template>
