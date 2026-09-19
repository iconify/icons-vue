<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn47u1y8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn47u1y8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:download-outline" /></template>
