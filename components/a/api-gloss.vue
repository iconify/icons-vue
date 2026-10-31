<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qu71zvknf.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/o/om60bcbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qu71zvknf wm-k"/><circle class="h_tsn8bxt wm-a"/><path class="om60bcbeq wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:api-gloss" /></template>
