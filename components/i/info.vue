<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_w8m9d2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e_w8m9d2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:info" /></template>
