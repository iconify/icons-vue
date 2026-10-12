<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j3_k57lwk.css';
import '../../css/e/e_9kbi40m.css';
import '../../css/k/k_my9vu2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j3_k57lwk"/><path class="e_9kbi40m"/><path class="k_my9vu2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bike-duotone" /></template>
