<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw4o7vbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cw4o7vbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bandcamp-logo-2-solid" /></template>
