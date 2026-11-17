<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly9882b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly9882b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-to-axis-dashed-horizontal" /></template>
