<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ks1gvgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e7ks1gvgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:camera" /></template>
