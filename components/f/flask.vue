<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi933-bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="qi933-bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:flask" /></template>
