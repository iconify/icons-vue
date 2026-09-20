<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecydh6bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ecydh6bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-right" /></template>
