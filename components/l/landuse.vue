<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9d4n4bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q9d4n4bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:landuse" /></template>
