<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jx7m1bbgd.css';
import '../../css/g/gb-ew8e1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="jx7m1bbgd"/><path clip-rule="evenodd" class="gb-ew8e1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-4-fill" /></template>
