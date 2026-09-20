<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yipfkb_er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yipfkb_er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-up-outline" /></template>
