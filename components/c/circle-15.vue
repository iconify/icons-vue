<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6i8ohboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w6i8ohboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:circle-15" /></template>
