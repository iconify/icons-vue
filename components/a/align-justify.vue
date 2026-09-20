<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upq_uz6fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upq_uz6fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:align-justify" /></template>
