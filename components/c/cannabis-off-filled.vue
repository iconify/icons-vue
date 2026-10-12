<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcygz2abe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcygz2abe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cannabis-off-filled" /></template>
