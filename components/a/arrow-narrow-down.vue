<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrsv_rb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrsv_rb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-narrow-down" /></template>
