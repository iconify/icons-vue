<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-dyqcuvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i-dyqcuvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:csv-outline" /></template>
