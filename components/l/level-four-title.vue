<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq2h2if7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fq2h2if7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:level-four-title" /></template>
