<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q17he9bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="q17he9bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-up-stroke-12" /></template>
