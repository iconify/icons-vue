<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiqmxbz-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="xiqmxbz-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:fonticons-fi" /></template>
