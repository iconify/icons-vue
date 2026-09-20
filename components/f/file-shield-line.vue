<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfxyhsbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxyhsbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-shield-line" /></template>
