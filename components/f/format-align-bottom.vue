<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdg7s_bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tdg7s_bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-align-bottom" /></template>
