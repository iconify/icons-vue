<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faj9-9r7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faj9-9r7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cloud-upload" /></template>
