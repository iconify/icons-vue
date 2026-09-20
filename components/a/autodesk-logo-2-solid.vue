<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgz1uxb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgz1uxb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:autodesk-logo-2-solid" /></template>
