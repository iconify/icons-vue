<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjh9fteip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjh9fteip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:hi-five-logo-solid" /></template>
