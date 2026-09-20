<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcq-wwlid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcq-wwlid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-cloud-logo-block" /></template>
