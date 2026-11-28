<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihu-h3pbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihu-h3pbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-up-solid" /></template>
