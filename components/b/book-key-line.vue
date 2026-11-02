<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icjv8bckw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icjv8bckw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-key-line" /></template>
