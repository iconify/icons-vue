<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6a0ktsjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6a0ktsjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:location-pin-filled" /></template>
