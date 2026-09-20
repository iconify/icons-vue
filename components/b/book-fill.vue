<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsya23z-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsya23z-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-fill" /></template>
