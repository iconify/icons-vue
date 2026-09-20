<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gij27ab9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gij27ab9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cut-solid" /></template>
