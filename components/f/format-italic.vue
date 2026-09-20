<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqb3xcc4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqb3xcc4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-italic" /></template>
