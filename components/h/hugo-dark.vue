<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzxayabpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzxayabpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hugo-dark" /></template>
