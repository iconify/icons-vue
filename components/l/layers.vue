<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo5ufz-lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo5ufz-lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:layers" /></template>
