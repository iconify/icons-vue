<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abx1n4ozg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abx1n4ozg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:amazon-alexa" /></template>
