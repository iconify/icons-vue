<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhh8rpb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhh8rpb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cup-soda-filled" /></template>
