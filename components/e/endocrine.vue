<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/k/kemrou4dr.css';
import '../../css/f/fp-t6vbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path clip-rule="evenodd" class="kemrou4dr"/><path class="fp-t6vbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:endocrine" /></template>
