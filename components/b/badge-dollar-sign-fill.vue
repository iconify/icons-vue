<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2ozp64hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2ozp64hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-dollar-sign-fill" /></template>
