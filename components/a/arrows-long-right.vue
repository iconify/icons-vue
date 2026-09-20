<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_qfkfbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f_qfkfbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrows-long-right" /></template>
