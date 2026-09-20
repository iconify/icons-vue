<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cge0fdcdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cge0fdcdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-upload-fill" /></template>
