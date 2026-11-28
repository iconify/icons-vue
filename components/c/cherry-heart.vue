<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8z-_ftin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8z-_ftin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cherry-heart" /></template>
