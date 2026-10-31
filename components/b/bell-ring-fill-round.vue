<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kobzaq9ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kobzaq9ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-ring-fill-round" /></template>
