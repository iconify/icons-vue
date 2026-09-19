<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wrpbjb6cy.css';
import '../../css/x/xrd-u7syi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="wrpbjb6cy"/><path clip-rule="evenodd" class="xrd-u7syi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:breast-pump-outline" /></template>
