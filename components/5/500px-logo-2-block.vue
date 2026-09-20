<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toef6xbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="toef6xbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:500px-logo-2-block" /></template>
