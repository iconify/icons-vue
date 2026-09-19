<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu1ylqbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yu1ylqbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-strikethrough" /></template>
