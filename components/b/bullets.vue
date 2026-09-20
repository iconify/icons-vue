<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4mi1abjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n4mi1abjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bullets" /></template>
