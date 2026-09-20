<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eih4zpioh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eih4zpioh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-venus-mars" /></template>
