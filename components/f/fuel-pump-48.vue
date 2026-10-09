<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a23qezmoi.css';
import '../../css/u/u6et4xbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a23qezmoi"/><path class="u6et4xbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-pump-48" /></template>
