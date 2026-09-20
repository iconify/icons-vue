<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osspv9bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osspv9bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-shield-2-fill" /></template>
