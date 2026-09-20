<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy_w0k1_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy_w0k1_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-sharp" /></template>
