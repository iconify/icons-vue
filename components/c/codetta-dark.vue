<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvydfubej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uvydfubej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:codetta-dark" /></template>
