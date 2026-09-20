<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drynjrbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="drynjrbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bicycle-key" /></template>
