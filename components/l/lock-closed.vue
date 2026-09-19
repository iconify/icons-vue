<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wq8x_6bdg.css';
import '../../css/x/xnzo5db6q.css';
import '../../css/b/bablryldg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="wq8x_6bdg"/><path class="xnzo5db6q"/><path class="bablryldg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:lock-closed" /></template>
