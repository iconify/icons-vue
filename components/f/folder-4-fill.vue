<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-65o2amg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-65o2amg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-4-fill" /></template>
