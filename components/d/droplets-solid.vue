<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpn7nrbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpn7nrbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:droplets-solid" /></template>
