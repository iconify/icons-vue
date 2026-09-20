<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn0u3gbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nn0u3gbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:artboard-outline" /></template>
