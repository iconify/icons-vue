<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j52dsfb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j52dsfb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:digital-ocean-logo-block" /></template>
