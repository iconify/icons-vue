<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuzo0466z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xuzo0466z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:fandom-logo-1-solid" /></template>
