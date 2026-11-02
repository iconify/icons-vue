<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da1jic_cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da1jic_cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cactus-2-fill" /></template>
