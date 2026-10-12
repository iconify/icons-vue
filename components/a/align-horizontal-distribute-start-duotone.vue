<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lh4_-wb-l.css';
import '../../css/b/bussztgsc.css';
import '../../css/i/ivyiakb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lh4_-wb-l"/><path class="bussztgsc"/><path class="ivyiakb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-horizontal-distribute-start-duotone" /></template>
