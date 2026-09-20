<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k59e6np9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k59e6np9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dome-with-flag" /></template>
