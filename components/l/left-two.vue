<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agewztbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="agewztbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:left-two" /></template>
