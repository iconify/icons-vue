<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5qjq0fnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5qjq0fnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-podcast-logo-block" /></template>
