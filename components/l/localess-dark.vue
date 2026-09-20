<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvh8ypbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fvh8ypbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:localess-dark" /></template>
