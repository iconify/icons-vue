<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/a9bnj9z9i.css';
import '../../css/l/lfqd9-qsa.css';
import '../../css/g/gnpj2gcot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a9bnj9z9i"/><path class="lfqd9-qsa"/><path class="gnpj2gcot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:church" /></template>
