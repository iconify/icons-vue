<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v420-060z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v420-060z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-roblox" /></template>
