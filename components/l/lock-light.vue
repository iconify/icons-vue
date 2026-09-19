<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/jz_tm_b_n.css';
import '../../css/q/q-s4sibmx.css';
import '../../css/b/b_4b31nqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="jz_tm_b_n"/><path class="q-s4sibmx"/><path class="b_4b31nqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:lock-light" /></template>
