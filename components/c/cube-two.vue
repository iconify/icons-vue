<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drdb5kbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="drdb5kbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cube-two" /></template>
