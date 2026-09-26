<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv054966h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lv054966h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-check-bold" /></template>
