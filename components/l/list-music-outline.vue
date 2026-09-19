<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu0mq3bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu0mq3bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:list-music-outline" /></template>
