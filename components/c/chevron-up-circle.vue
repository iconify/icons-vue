<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajwjw6b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ajwjw6b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chevron-up-circle" /></template>
