<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o4s-r7b5o.css';
import '../../css/p/pj5m5abjl.css';
import '../../css/w/whg6u3fco.css';
import '../../css/q/qeflvnj7y.css';
import '../../css/v/v5br42bry.css';
import '../../css/w/wrlch1b9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="o4s-r7b5o"/><path clip-rule="evenodd" class="pj5m5abjl"/><path class="whg6u3fco"/><path clip-rule="evenodd" class="qeflvnj7y"/><path clip-rule="evenodd" class="v5br42bry"/><path clip-rule="evenodd" class="wrlch1b9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:countdown-print" /></template>
