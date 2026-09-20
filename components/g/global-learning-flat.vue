<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/onoh73b6l.css';
import '../../css/v/v42xnhcko.css';
import '../../css/d/d59qf6ssp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="onoh73b6l"/><path class="v42xnhcko"/><path class="d59qf6ssp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:global-learning-flat" /></template>
