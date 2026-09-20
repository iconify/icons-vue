<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6_bgxfso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i6_bgxfso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:app-store-flat" /></template>
