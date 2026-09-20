<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqzxe4bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqzxe4bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:code" /></template>
