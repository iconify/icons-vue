<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g-hcumvny.css';
import '../../css/w/w_h8p_b7m.css';
import '../../css/y/ymymmsr_a.css';
import '../../css/i/ivwyrzb9n.css';
import '../../css/j/jrqh271eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="g-hcumvny"/><path class="w_h8p_b7m"/><path class="ymymmsr_a"/><path class="ivwyrzb9n"/><path class="jrqh271eq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:arrows-spin" /></template>
