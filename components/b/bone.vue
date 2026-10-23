<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu242qbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu242qbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bone" /></template>
