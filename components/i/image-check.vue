<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r2qplccuz.css';
import '../../css/h/h-m8eqbos.css';
import '../../css/i/icf0rgbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r2qplccuz"/><path clip-rule="evenodd" class="h-m8eqbos"/><path class="icf0rgbji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image-check" /></template>
