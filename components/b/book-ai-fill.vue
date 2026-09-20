<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqj44p9dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqj44p9dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-ai-fill" /></template>
