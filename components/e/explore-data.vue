<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwptshk5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rwptshk5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:explore-data" /></template>
