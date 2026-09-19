<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5we_2bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c5we_2bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:block-five" /></template>
