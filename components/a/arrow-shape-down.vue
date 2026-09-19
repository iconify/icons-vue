<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1xn9bcet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f1xn9bcet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-down" /></template>
