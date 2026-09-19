<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efo1t8wme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="efo1t8wme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:chopsticks-fork" /></template>
