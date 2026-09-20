<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhr-1eb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhr-1eb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:androidauto-logo-block" /></template>
