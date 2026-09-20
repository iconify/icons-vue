<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz33hqbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="yz33hqbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-float-right" /></template>
