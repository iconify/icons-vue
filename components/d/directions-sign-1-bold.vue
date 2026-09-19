<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_fyccblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g_fyccblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:directions-sign-1-bold" /></template>
