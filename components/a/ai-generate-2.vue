<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcqw2bbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcqw2bbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ai-generate-2" /></template>
