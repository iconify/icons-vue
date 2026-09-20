<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhqz6verd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhqz6verd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-minus" /></template>
