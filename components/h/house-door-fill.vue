<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fur479xqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fur479xqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:house-door-fill" /></template>
