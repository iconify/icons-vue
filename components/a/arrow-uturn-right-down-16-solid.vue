<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3wq7xjha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o3wq7xjha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-right-down-16-solid" /></template>
