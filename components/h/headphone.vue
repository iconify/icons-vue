<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nc4rl_brn.css';
import '../../css/a/ayaqdo9ve.css';
import '../../css/z/za5ig0byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nc4rl_brn"/><path class="ayaqdo9ve"/><path class="za5ig0byw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:headphone" /></template>
