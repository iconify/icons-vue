<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcb7n_v4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lcb7n_v4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-outline-with-left-half" /></template>
