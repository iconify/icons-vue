<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfrim3bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nfrim3bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:amount-down-two-outline" /></template>
