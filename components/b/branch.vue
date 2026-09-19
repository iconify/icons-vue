<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7j09yb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":520};
const content = `<path class="l7j09yb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:branch" /></template>
