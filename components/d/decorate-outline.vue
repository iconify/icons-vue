<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuz046bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nuz046bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:decorate-outline" /></template>
