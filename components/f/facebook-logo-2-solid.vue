<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9aqz85-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9aqz85-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:facebook-logo-2-solid" /></template>
