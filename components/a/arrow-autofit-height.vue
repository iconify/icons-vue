<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1-vdhbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1-vdhbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-autofit-height" /></template>
