<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrzuqrbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jrzuqrbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:codepen-dark" /></template>
