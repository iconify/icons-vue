<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apdg82bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="apdg82bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-solid" /></template>
