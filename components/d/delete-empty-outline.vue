<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7zv08aim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7zv08aim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:delete-empty-outline" /></template>
