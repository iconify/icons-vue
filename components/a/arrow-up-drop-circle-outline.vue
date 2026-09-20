<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by007idoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by007idoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-drop-circle-outline" /></template>
