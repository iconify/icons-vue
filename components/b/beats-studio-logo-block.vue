<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8us4sbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8us4sbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:beats-studio-logo-block" /></template>
