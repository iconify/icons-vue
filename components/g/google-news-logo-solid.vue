<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhcw76f0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhcw76f0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-news-logo-solid" /></template>
