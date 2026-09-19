<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtw0ggbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtw0ggbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hands-support-filled" /></template>
