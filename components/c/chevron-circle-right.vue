<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grwh7o55x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="grwh7o55x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-circle-right" /></template>
