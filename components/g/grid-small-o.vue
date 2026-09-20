<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy7_qtwkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jy7_qtwkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:grid-small-o" /></template>
