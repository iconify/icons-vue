<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrvn9ab9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrvn9ab9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-right" /></template>
