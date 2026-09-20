<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzh6r_7vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzh6r_7vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-column-stacked" /></template>
