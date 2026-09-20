<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viwnlk27h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="viwnlk27h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:activity-log" /></template>
