<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r34rufvhd.css';
import '../../css/v/v51lyqb9f.css';
import '../../css/d/dfm337b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r34rufvhd"/><path class="v51lyqb9f"/><path class="dfm337b_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:emergency-post-24px" /></template>
