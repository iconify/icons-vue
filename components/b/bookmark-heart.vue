<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmi3aw10y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmi3aw10y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-heart" /></template>
