<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5fta5b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l5fta5b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-right-fill" /></template>
