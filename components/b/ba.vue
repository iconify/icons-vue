<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l-nvvtu9k.css';
import '../../css/c/cj9i99glq.css';
import '../../css/z/z1k0_nbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l-nvvtu9k"/><path class="cj9i99glq"/><path class="z1k0_nbcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:ba" /></template>
