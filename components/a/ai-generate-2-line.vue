<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok3bfoi4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok3bfoi4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ai-generate-2-line" /></template>
