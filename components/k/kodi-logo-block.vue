<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj3uoc7wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mj3uoc7wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:kodi-logo-block" /></template>
