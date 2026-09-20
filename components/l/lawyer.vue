<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-jd97b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="j-jd97b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:lawyer" /></template>
