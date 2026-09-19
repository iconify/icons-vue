<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gyf0ee2rr.css';
import '../../css/g/gofpikhwp.css';
import '../../css/a/azg3zbcbt.css';
import '../../css/y/y6pici8-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gyf0ee2rr"/><path class="gofpikhwp"/><path class="azg3zbcbt"/><path class="y6pici8-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:gh" /></template>
