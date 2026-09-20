<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sln4qdbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sln4qdbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:captions-off" /></template>
