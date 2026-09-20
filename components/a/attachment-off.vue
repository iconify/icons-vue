<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwrdfr5cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwrdfr5cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:attachment-off" /></template>
