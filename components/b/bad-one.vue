<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhald_j0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mhald_j0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:bad-one" /></template>
