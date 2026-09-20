<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rl-fbwnpe.css';
import '../../css/q/qhz8-fyzm.css';
import '../../css/o/obibidbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rl-fbwnpe"/><path class="qhz8-fyzm"/><path class="obibidbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:film-roll-1-flat" /></template>
