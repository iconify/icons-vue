<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_sj2cbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_sj2cbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bing-logo-2-block" /></template>
