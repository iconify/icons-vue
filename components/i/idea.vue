<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8x-vccbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="d8x-vccbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:idea" /></template>
