<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6bqpgb6d.css';
import '../../css/r/rasj23r5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v6bqpgb6d"/><path class="rasj23r5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:flag-checkered" /></template>
