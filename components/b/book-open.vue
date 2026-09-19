<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvilx1q3c.css';
import '../../css/p/pqwcjgxcc.css';
import '../../css/x/x9ylqsbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="kvilx1q3c"><path class="pqwcjgxcc"/><path class="x9ylqsbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:book-open" /></template>
