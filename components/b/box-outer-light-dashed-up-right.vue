<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tctkn4c7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tctkn4c7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-dashed-up-right" /></template>
