<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/if838_bko.css';
import '../../css/z/z59g61bbc.css';
import '../../css/l/l788tm9oc.css';
import '../../css/j/jhb5hjq3f.css';
import '../../css/t/twhx2sbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="if838_bko"/><path clip-rule="evenodd" class="z59g61bbc"/><path clip-rule="evenodd" class="l788tm9oc"/><path clip-rule="evenodd" class="jhb5hjq3f"/><path clip-rule="evenodd" class="twhx2sbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:leave" /></template>
