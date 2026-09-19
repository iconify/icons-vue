<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cne_cj2pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cne_cj2pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-panel" /></template>
