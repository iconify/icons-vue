<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1016ldf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1016ldf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-trending-up" /></template>
