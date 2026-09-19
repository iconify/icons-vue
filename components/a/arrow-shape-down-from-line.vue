<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-eltu37y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g-eltu37y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-down-from-line" /></template>
