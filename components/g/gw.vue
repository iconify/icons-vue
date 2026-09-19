<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mbv0z8b9w.css';
import '../../css/e/eilml7bjc.css';
import '../../css/r/ruftofbgy.css';
import '../../css/c/cc4a2vcxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mbv0z8b9w"/><path class="eilml7bjc"/><path class="ruftofbgy"/><path class="cc4a2vcxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:gw" /></template>
