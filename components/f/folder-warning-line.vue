<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gav38t2og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gav38t2og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-warning-line" /></template>
