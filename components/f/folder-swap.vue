<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi-2hybse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi-2hybse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-swap" /></template>
