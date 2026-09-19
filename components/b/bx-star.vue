<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7sv0zffi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7sv0zffi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-star" /></template>
