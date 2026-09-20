<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue-h57b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue-h57b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:image-ai-filled" /></template>
