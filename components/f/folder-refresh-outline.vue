<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3hxdddeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3hxdddeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-refresh-outline" /></template>
