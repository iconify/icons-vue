<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwnoa1buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwnoa1buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:focus-2-fill" /></template>
