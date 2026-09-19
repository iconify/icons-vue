<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug2uzzb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ug2uzzb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:crib" /></template>
