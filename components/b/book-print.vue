<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k6zqa2bdl.css';
import '../../css/g/g0l_0wbda.css';
import '../../css/r/rei6xduai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="k6zqa2bdl"/><path clip-rule="evenodd" class="g0l_0wbda"/><path clip-rule="evenodd" class="rei6xduai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:book-print" /></template>
