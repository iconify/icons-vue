<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lamx9gjea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lamx9gjea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-d10-outline" /></template>
