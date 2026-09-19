<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7cpy6-3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t7cpy6-3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-presentation-stroke-12" /></template>
