<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-u1sk9yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n-u1sk9yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:drizzle-orm" /></template>
