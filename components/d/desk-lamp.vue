<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7f9_ccuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7f9_ccuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:desk-lamp" /></template>
