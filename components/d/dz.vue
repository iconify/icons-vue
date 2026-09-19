<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q0tuw_b0b.css';
import '../../css/y/yn23mu4wr.css';
import '../../css/w/wqgqwwulx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q0tuw_b0b"/><path class="yn23mu4wr"/><path class="wqgqwwulx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:dz" /></template>
