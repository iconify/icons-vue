<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7l9mq-pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d7l9mq-pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:door" /></template>
