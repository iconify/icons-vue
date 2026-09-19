<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdt38crvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bdt38crvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:filter-one" /></template>
