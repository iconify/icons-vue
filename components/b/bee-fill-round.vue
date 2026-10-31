<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d31hp5hth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d31hp5hth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bee-fill-round" /></template>
