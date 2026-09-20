<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypkmywbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypkmywbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:edit-pdf" /></template>
