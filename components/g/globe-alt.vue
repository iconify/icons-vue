<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do3v0r02q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do3v0r02q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:globe-alt" /></template>
