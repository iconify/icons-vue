<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fro30fydk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fro30fydk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:loom-logo" /></template>
