<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtzvfs7nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gtzvfs7nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:factory" /></template>
