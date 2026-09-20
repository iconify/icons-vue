<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c6yq9sr9t.css';
import '../../css/o/orn1n2npw.css';
import '../../css/v/v88mkbbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c6yq9sr9t"/><path class="orn1n2npw"/><path clip-rule="evenodd" class="v88mkbbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-minimalistic-outline" /></template>
