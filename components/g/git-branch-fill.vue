<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vipz4vb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vipz4vb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-branch-fill" /></template>
