<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs2qo9b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs2qo9b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-alert-outline" /></template>
