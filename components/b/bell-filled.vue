<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/solvxzivd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="solvxzivd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-filled" /></template>
