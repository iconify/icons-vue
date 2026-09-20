<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j0a576glu.css';
import '../../css/d/dnug5tb-m.css';
import '../../css/p/pm7abs72w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="j0a576glu"/><path class="dnug5tb-m"/><path class="pm7abs72w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:copy-2-flat" /></template>
