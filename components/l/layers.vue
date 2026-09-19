<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gg9a5mbfj.css';
import '../../css/p/phqvtfx7h.css';
import '../../css/t/t5rgi3bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="gg9a5mbfj"/><path class="phqvtfx7h"/><path class="t5rgi3bje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:layers" /></template>
