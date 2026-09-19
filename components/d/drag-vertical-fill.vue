<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4w-4_rrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4w-4_rrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:drag-vertical-fill" /></template>
