<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zsd-xescs.css';
import '../../css/r/ray9_ac3o.css';
import '../../css/p/pmz80t_au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zsd-xescs"/><path class="ray9_ac3o"/><path class="pmz80t_au"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:ie" /></template>
