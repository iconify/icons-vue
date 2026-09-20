<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs9dfd7xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fs9dfd7xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-outline" /></template>
