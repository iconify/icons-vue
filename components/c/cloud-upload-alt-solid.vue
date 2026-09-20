<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_1h_uu6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g_1h_uu6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cloud-upload-alt-solid" /></template>
