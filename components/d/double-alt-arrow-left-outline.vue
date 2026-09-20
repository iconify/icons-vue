<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf1q-gaub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf1q-gaub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-left-outline" /></template>
