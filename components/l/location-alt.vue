<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3fekvbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u3fekvbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:location-alt" /></template>
