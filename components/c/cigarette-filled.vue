<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1vs7vb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1vs7vb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cigarette-filled" /></template>
