<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z948rhb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z948rhb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:doorbell-video" /></template>
