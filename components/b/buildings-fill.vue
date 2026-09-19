<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdggac0rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zdggac0rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:buildings-fill" /></template>
