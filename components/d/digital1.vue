<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6kw9kb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j6kw9kb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital1" /></template>
