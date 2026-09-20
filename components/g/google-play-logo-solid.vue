<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww279mbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ww279mbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-play-logo-solid" /></template>
