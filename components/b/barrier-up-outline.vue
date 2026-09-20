<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k785w0v7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k785w0v7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:barrier-up-outline" /></template>
