<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-v236g8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k-v236g8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:circle-house" /></template>
