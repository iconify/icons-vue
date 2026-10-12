<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2_8y6pzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2_8y6pzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:grid-2x2-x-filled" /></template>
