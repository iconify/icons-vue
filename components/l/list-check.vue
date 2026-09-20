<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz6uku90w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz6uku90w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-check" /></template>
