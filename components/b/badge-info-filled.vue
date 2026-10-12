<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5zj4ufve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5zj4ufve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-info-filled" /></template>
