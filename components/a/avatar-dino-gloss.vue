<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9gcjfb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9gcjfb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-dino-gloss" /></template>
