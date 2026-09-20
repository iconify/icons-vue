<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1mjunbsu.css';
import '../../css/d/d9rbyu3nx.css';
import '../../css/f/flen3tbdj.css';
import '../../css/t/t1i8eebpo.css';
import '../../css/y/ykhh1jp9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<mask id="SVGwjo0bdvJ" class="n1mjunbsu"><path class="d9rbyu3nx"/></mask><g class="flen3tbdj"><path class="t1i8eebpo"/><path mask="url(#SVGwjo0bdvJ)" class="ykhh1jp9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:info" /></template>
