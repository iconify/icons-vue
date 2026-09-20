<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-px0gyax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="l-px0gyax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:bell" /></template>
