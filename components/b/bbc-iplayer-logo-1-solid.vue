<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl386l-8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl386l-8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bbc-iplayer-logo-1-solid" /></template>
