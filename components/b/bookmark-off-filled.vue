<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5edrzb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5edrzb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bookmark-off-filled" /></template>
