<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gazz5ebes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gazz5ebes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bookmark-solid" /></template>
