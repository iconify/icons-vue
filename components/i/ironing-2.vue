<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv9cyv-nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv9cyv-nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ironing-2" /></template>
