<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnz4es2ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnz4es2ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:apps-2-add-fill" /></template>
