<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldopy_b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldopy_b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-arrow-down-left-filled" /></template>
