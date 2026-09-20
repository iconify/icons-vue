<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy3vjrbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cy3vjrbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clockwise-solid" /></template>
