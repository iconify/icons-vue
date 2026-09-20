<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ingufyn2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ingufyn2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headphones-slash-16-solid" /></template>
