<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvyvww6gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvyvww6gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-stadia-logo" /></template>
