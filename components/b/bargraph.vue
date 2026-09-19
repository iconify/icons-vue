<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcjzqc7he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":32};
const content = `<path class="bcjzqc7he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:bargraph" /></template>
