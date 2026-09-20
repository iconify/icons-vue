<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daap6e5ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daap6e5ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:coding-apps-website-apps-add-widget-bold" /></template>
