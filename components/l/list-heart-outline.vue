<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/danvxv9gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="danvxv9gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-heart-outline" /></template>
