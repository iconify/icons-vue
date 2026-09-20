<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt8wgkbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt8wgkbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hulu" /></template>
