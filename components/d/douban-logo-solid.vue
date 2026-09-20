<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l86hmv1mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l86hmv1mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:douban-logo-solid" /></template>
