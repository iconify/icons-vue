<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rhdob0q5v.css';
import '../../css/x/xli-_5yuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rhdob0q5v"/><path class="xli-_5yuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:alarm-fill" /></template>
