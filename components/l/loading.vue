<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znl267sqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znl267sqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:loading" /></template>
