<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctw_mi0zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctw_mi0zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:instagram-logo-2-block" /></template>
