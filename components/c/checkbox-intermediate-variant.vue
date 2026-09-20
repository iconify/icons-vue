<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzijn6bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzijn6bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkbox-intermediate-variant" /></template>
