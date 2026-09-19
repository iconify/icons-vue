<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igl8irugt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="igl8irugt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:grid-view" /></template>
