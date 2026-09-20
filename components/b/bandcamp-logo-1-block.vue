<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti74s-boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti74s-boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bandcamp-logo-1-block" /></template>
