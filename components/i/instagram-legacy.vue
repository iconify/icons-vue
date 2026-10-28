<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-swyr_3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":146};
const content = `<path class="v-swyr_3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:instagram-legacy" /></template>
