<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy7gu6zfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cy7gu6zfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-home-logo-block" /></template>
