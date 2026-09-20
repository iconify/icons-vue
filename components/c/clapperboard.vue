<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/rim3hrmwm.css';
import '../../css/r/r8ref12dh.css';
import '../../css/o/o8ul2gb7f.css';
import '../../css/c/c_i5kdq5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="rim3hrmwm"/><path class="r8ref12dh"/><path class="o8ul2gb7f"/><path class="c_i5kdq5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:clapperboard" /></template>
