<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csrxh4e4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="csrxh4e4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:exchange" /></template>
