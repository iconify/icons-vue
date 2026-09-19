<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol1qgland.css';
import '../../css/l/lu-nqrbmy.css';
import '../../css/a/ayje7ibqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ol1qgland"><path class="lu-nqrbmy"/><path class="ayje7ibqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:intermediate-mode" /></template>
