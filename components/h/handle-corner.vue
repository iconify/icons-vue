<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndq1rxbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ndq1rxbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:handle-corner" /></template>
