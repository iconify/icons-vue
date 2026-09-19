<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/ie9tjobji.css';
import '../../css/b/bd-ms75ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ie9tjobji"/><path class="bd-ms75ny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:house-with-garden" /></template>
