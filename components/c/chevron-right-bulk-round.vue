<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4gn4qb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4gn4qb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-right-bulk-round" /></template>
