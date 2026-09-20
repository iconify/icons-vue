<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od05kr4ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="od05kr4ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:askfm-logo-block" /></template>
