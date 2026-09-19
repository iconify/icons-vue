<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_4zlfbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k_4zlfbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:gluten" /></template>
