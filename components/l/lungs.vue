<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r78ox6b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r78ox6b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:lungs" /></template>
