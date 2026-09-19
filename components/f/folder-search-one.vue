<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/g/gpbfd-bbj.css';
import '../../css/d/ds9nz3qrr.css';
import '../../css/x/xj9-7bcyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="gpbfd-bbj"/><circle class="ds9nz3qrr"/><path class="xj9-7bcyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:folder-search-one" /></template>
