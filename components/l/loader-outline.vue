<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzd5q4bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rzd5q4bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:loader-outline" /></template>
