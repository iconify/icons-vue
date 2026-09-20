<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqysygbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqysygbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:download-cloud-line" /></template>
