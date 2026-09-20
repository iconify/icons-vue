<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u3f7ln7wn.css';
import '../../css/a/a02p_nb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u3f7ln7wn"/><path clip-rule="evenodd" class="a02p_nb_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-down-bold-duotone" /></template>
