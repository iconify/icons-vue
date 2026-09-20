<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tss2zerei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tss2zerei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:loom-logo-solid" /></template>
