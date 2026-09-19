<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4eaeeb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4eaeeb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:incognito-filled" /></template>
