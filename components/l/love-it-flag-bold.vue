<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unprg6b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unprg6b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:love-it-flag-bold" /></template>
