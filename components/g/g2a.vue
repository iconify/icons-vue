<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueg6d4b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueg6d4b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:g2a" /></template>
