<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o429npazi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o429npazi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:etsy-logo-block" /></template>
