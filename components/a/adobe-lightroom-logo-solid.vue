<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlc4d9v9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlc4d9v9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-lightroom-logo-solid" /></template>
