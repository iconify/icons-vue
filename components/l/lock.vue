<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr079etta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dr079etta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:lock" /></template>
