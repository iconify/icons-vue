<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haj0-xbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haj0-xbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:container-fill-round" /></template>
