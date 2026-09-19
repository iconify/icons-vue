<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c39_9dbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c39_9dbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:home" /></template>
