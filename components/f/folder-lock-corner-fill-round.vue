<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap8e4tb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap8e4tb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-lock-corner-fill-round" /></template>
