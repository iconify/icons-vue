<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwno7hb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gwno7hb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:eraser-fill" /></template>
