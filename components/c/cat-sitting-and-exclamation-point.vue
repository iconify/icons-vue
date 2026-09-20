<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec8qg8bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ec8qg8bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cat-sitting-and-exclamation-point" /></template>
