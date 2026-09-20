<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylkgs53ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylkgs53ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:loader-linear" /></template>
