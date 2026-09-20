<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euz9sykji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euz9sykji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-wrench" /></template>
