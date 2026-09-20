<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8j-1-v7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8j-1-v7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-outline" /></template>
