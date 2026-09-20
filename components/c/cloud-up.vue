<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lck50fbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lck50fbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:cloud-up" /></template>
