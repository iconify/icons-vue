<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avc2a9nxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avc2a9nxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:braces" /></template>
