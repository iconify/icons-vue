<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceb7hcupy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ceb7hcupy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:arrows-long-down" /></template>
