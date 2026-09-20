<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm2ja9gvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm2ja9gvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-masonry-fill" /></template>
