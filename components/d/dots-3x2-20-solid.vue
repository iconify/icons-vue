<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2gpyo16f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e2gpyo16f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x2-20-solid" /></template>
