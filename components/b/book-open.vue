<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqc6o2bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pqc6o2bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:book-open" /></template>
