<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtrligblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtrligblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bowling-outline" /></template>
