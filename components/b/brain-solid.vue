<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu12vxbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eu12vxbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:brain-solid" /></template>
