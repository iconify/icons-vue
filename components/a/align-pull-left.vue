<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji4dstbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ji4dstbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:align-pull-left" /></template>
