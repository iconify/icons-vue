<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owf71glth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owf71glth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-remove" /></template>
