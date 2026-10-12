<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1coifbia.css';
import '../../css/s/s6d7cubjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1coifbia"/><path class="s6d7cubjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:heart-plus-filled" /></template>
