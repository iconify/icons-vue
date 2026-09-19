<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h20g5bcub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h20g5bcub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hourglass-top" /></template>
