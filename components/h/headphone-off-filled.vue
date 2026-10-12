<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blx7dw47b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blx7dw47b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:headphone-off-filled" /></template>
