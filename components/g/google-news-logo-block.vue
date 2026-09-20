<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpj70b3ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rpj70b3ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-news-logo-block" /></template>
