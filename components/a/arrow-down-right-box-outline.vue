<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nffh7rbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nffh7rbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-down-right-box-outline" /></template>
