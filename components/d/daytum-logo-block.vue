<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/incwcnbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="incwcnbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:daytum-logo-block" /></template>
