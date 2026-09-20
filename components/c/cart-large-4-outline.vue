<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zcd39qb3r.css';
import '../../css/b/bv8zrozgd.css';
import '../../css/e/en89jw64i.css';
import '../../css/p/pvdyq3brk.css';
import '../../css/x/x5-t90vnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zcd39qb3r"/><path class="bv8zrozgd"/><path clip-rule="evenodd" class="en89jw64i"/><path clip-rule="evenodd" class="pvdyq3brk"/><path clip-rule="evenodd" class="x5-t90vnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-large-4-outline" /></template>
