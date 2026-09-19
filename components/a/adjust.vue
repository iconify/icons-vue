<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_b2heo5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="e_b2heo5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:adjust" /></template>
