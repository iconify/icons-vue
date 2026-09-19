<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0f8p3u2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0f8p3u2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:forward-slash-circle-filled" /></template>
