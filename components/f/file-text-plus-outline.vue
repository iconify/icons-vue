<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdw1bnmki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdw1bnmki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-text-plus-outline" /></template>
