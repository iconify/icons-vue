<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otgxtbbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otgxtbbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-from-axis-vertical" /></template>
