<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7yrp7bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7yrp7bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cookie-solid" /></template>
