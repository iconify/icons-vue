<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3pvgtaya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s3pvgtaya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:location-arrow" /></template>
