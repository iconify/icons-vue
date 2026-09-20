<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_fudbcsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_fudbcsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-account" /></template>
