<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ymvtb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ymvtb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:earbuds-off-filled" /></template>
