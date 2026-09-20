<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm0gbtz0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pm0gbtz0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrows" /></template>
