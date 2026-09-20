<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcyll2bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pcyll2bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-down-left-right" /></template>
