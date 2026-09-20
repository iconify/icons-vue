<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj0gtbbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj0gtbbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:facebook-logo-1" /></template>
