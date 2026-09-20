<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnmoie6ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xnmoie6ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gowalla-logo-2-block" /></template>
