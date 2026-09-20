<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai7oghm0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai7oghm0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:cup-saucer" /></template>
