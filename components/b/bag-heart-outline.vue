<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1mpvmb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y1mpvmb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-heart-outline" /></template>
