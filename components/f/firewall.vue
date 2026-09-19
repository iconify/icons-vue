<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f88q_7b9p.css';
import '../../css/b/bkdyu3kxb.css';
import '../../css/g/gm_nkzbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="f88q_7b9p"/><path clip-rule="evenodd" class="bkdyu3kxb"/><path class="gm_nkzbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:firewall" /></template>
