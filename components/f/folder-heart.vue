<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq3o2etsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq3o2etsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-heart" /></template>
