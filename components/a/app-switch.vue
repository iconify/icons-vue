<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv_oq7_es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bv_oq7_es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:app-switch" /></template>
