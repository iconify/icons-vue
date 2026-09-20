<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwbk_kbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cwbk_kbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:amd-logo-block" /></template>
