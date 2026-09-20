<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-d9zgwqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-d9zgwqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-key" /></template>
