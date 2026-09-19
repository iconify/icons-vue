<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjzvy6bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hjzvy6bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:exclamation" /></template>
