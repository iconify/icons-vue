<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijuo7pu9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ijuo7pu9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:magic-wand-sparkles" /></template>
