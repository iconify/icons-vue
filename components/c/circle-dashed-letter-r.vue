<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhs9oua6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhs9oua6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-r" /></template>
