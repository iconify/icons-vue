<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uau_pxbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uau_pxbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:book" /></template>
