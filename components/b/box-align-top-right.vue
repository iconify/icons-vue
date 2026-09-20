<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv717kbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv717kbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-top-right" /></template>
