<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0zj1p-mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0zj1p-mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eyedropper-fill-round" /></template>
