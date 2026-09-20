<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3pj0pbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3pj0pbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:crowdin-logo-block" /></template>
