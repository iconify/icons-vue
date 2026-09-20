<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2amfk51n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2amfk51n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:figma-logo-solid" /></template>
