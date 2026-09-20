<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc8ccm9by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc8ccm9by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ai-generate-2-fill" /></template>
