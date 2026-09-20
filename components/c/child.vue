<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih-dr08ex.css';
import '../../css/n/ngqdbfb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ih-dr08ex"/><path class="ngqdbfb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:child" /></template>
