<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr5jt2bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wr5jt2bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:checkbox-cross" /></template>
