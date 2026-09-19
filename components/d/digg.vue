<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmvozccrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="tmvozccrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:digg" /></template>
