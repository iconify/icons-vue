<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_z-ilrca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_z-ilrca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:apple-ios-logo-3-block" /></template>
