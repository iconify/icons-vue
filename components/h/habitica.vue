<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9vwi7blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g9vwi7blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:habitica" /></template>
