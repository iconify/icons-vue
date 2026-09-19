<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eik3fo4xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eik3fo4xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bottle-one" /></template>
