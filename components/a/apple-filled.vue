<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo4eunb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo4eunb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:apple-filled" /></template>
