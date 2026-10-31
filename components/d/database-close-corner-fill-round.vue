<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv444039r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv444039r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-close-corner-fill-round" /></template>
