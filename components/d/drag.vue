<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqfj8n7ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqfj8n7ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:drag" /></template>
