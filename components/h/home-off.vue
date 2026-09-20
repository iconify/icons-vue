<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya7fk0fzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya7fk0fzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-off" /></template>
