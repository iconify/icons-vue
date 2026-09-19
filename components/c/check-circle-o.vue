<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r97i27b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="r97i27b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:check-circle-o" /></template>
